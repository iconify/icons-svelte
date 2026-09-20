<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6bg_5m0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6bg_5m0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-21-small" {...props}></Icon>
