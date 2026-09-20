<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebi4uebqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ebi4uebqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:right-indent-alt" {...props}></Icon>
