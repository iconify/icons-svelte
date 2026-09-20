<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp6em2bme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wp6em2bme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:codemirror" {...props}></Icon>
