<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw2gtd80r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qw2gtd80r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bucket-filled" {...props}></Icon>
