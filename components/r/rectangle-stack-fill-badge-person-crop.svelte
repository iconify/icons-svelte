<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-jbc412p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="p-jbc412p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:rectangle-stack-fill-badge-person-crop" {...props}></Icon>
