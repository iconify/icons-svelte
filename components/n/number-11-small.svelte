<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d050ttizf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d050ttizf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-11-small" {...props}></Icon>
