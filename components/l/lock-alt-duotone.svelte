<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zcm0jnb5j.css';
import '../../css/l/lok2_9bwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zcm0jnb5j"/><path class="lok2_9bwy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:lock-alt-duotone" {...props}></Icon>
