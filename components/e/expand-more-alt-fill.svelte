<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwyk2y6_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uwyk2y6_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:expand-more-alt-fill" {...props}></Icon>
