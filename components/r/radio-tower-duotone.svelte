<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqwxuxk7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary tqwxuxk7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:radio-tower-duotone" {...props}></Icon>
