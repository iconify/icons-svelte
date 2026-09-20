<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf_46ablw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cf_46ablw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:radioactive-2-flat" {...props}></Icon>
