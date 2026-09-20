<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8b93bckm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j8b93bckm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:money-bill-wave" {...props}></Icon>
