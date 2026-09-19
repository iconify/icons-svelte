<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q79mtubzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q79mtubzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:minus" {...props}></Icon>
