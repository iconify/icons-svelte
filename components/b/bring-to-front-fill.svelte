<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prrr1qb-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="prrr1qb-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bring-to-front-fill" {...props}></Icon>
