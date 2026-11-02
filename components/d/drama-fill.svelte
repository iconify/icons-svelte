<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb-6bobka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qb-6bobka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:drama-fill" {...props}></Icon>
