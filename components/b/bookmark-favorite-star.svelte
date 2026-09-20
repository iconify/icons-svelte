<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3xtuk_0z.css';
import '../../css/k/kz-uz9bcv.css';
import '../../css/b/b8wlprfnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="l3xtuk_0z"><path class="kz-uz9bcv"/><path class="b8wlprfnu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:bookmark-favorite-star" {...props}></Icon>
