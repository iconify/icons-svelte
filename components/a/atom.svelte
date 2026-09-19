<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z59rc0x6w.css';
import '../../css/k/k70t2o__t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z59rc0x6w"/><path class="k70t2o__t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:atom" {...props}></Icon>
