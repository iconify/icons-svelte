<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0t0l7b9n.css';
import '../../css/b/bzew_ab9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v0t0l7b9n"/><path class="bzew_ab9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:crunchyroll" {...props}></Icon>
