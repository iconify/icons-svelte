<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jeyiptbtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jeyiptbtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-9-plus-box-multiple-outline" {...props}></Icon>
