<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywe0yq7db.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ywe0yq7db"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:exchange-euro-fill" {...props}></Icon>
