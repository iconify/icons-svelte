<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-8yzyb5a.css';
import '../../css/j/jy7k-3hfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="e-8yzyb5a"/><path class="jy7k-3hfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-emergency" {...props}></Icon>
