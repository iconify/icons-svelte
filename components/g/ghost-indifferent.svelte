<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4mr0ebnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4mr0ebnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:ghost-indifferent" {...props}></Icon>
