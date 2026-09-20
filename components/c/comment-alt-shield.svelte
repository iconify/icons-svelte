<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrj4jebuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yrj4jebuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:comment-alt-shield" {...props}></Icon>
