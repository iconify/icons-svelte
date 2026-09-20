<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_lv-h22b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_lv-h22b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:play-football-line" {...props}></Icon>
