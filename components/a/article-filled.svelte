<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1qn8nb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1qn8nb_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:article-filled" {...props}></Icon>
