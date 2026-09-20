<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_t6k4brw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="w_t6k4brw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:erlenmeyer-flask-remix" {...props}></Icon>
