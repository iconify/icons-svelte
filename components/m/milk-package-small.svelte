<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eym_g24ps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="eym_g24ps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:milk-package-small" {...props}></Icon>
