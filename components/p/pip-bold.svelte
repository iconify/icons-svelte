<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udz5nqb7v.css';
import '../../css/c/cez-1qbcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udz5nqb7v"/><path class="cez-1qbcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pip-bold" {...props}></Icon>
