<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oh-n76h3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oh-n76h3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:hammer" {...props}></Icon>
