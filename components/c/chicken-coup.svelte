<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krckgcb5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="krckgcb5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:chicken-coup" {...props}></Icon>
