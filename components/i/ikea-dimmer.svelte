<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syoi-0qiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="syoi-0qiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ikea-dimmer" {...props}></Icon>
