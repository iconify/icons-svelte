<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udz5nqb7v.css';
import '../../css/k/kdob9slbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udz5nqb7v"/><path class="kdob9slbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pip-bold-duotone" {...props}></Icon>
