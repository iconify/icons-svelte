<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb7vvlbro.css';
import '../../css/y/y7ajkhrwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="qb7vvlbro"/><path class="y7ajkhrwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cloud-sun-bold-duotone" {...props}></Icon>
