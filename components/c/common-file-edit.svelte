<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_jabp8zg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_jabp8zg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:common-file-edit" {...props}></Icon>
