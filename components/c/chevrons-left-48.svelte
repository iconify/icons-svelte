<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h09i3hbzu.css';
import '../../css/q/q_dqg26dw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h09i3hbzu"/><path class="q_dqg26dw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chevrons-left-48" {...props}></Icon>
