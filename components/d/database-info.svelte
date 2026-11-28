<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxnyeh7xw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxnyeh7xw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:database-info" {...props}></Icon>
