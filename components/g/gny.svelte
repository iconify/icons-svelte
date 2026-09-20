<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw9f3qb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cw9f3qb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:gny" {...props}></Icon>
