<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgrx5d4dy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mgrx5d4dy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:heart-light" {...props}></Icon>
