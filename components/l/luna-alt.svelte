<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhi3qacmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhi3qacmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:luna-alt" {...props}></Icon>
