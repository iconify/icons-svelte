<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozmf5ipva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ozmf5ipva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:git-pull-request-fill" {...props}></Icon>
