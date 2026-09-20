<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ianmb7bxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ianmb7bxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:maximize-fill" {...props}></Icon>
