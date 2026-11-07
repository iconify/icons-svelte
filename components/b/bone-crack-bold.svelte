<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avz4_kb7i.css';
import '../../css/b/b2_20abta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avz4_kb7i"/><path class="b2_20abta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bone-crack-bold" {...props}></Icon>
