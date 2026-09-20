<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtdoon55r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qtdoon55r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-28-small" {...props}></Icon>
