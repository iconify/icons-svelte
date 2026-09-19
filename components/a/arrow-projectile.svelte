<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or5jkcb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="or5jkcb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-projectile" {...props}></Icon>
