<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2m6oob6i.css';
import '../../css/k/kbnhcials.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o2m6oob6i"/><path class="kbnhcials"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:planet-bold-duotone" {...props}></Icon>
