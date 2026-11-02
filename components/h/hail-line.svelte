<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecs7zwxur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ecs7zwxur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hail-line" {...props}></Icon>
