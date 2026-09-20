<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idq-hxb8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="idq-hxb8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-in-up-left-dashed-panel-sharp-fill" {...props}></Icon>
