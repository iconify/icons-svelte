<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hiu-slybi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hiu-slybi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pen-edit-circle-alt" {...props}></Icon>
