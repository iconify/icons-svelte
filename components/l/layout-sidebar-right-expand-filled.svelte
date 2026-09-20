<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emr3p-0fx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="emr3p-0fx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:layout-sidebar-right-expand-filled" {...props}></Icon>
