<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp_ozk4rx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pp_ozk4rx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:nanoleaf-holiday-string" {...props}></Icon>
