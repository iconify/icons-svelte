<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6w97ub9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6w97ub9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:cloud-drizzle" {...props}></Icon>
