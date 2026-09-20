<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eixj8y_wd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eixj8y_wd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-hexo" {...props}></Icon>
