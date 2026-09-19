<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_olkpbwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v_olkpbwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:division-sign-in-square" {...props}></Icon>
