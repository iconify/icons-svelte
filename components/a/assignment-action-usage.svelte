<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcxg7mqrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kcxg7mqrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:assignment-action-usage" {...props}></Icon>
