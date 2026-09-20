<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9bk5cbdt.css';
import '../../css/k/k2_62w1sw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v9bk5cbdt"/><path class="k2_62w1sw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:eye-solid" {...props}></Icon>
