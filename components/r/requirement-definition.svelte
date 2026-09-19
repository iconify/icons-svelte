<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eocglkw9k.css';
import '../../css/a/awir01b8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eocglkw9k"/><path class="awir01b8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:requirement-definition" {...props}></Icon>
