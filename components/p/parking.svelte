<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0t22yxla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z0t22yxla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:parking" {...props}></Icon>
