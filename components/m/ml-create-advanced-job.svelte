<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq9_xubku.css';
import '../../css/x/xdtlmkksx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qq9_xubku"/><path class="ouiIcon__fillSecondary xdtlmkksx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:ml-create-advanced-job" {...props}></Icon>
