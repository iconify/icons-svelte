<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6c56ebta.css';
import '../../css/u/ulpze-4na.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6c56ebta"/><path class="ulpze-4na"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:creators-club" {...props}></Icon>
