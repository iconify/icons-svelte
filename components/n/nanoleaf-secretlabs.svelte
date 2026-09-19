<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8rclib1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j8rclib1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:nanoleaf-secretlabs" {...props}></Icon>
