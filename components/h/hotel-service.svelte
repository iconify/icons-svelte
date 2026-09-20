<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb8m35buc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cb8m35buc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hotel-service" {...props}></Icon>
