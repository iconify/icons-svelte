<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcas9bc8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kcas9bc8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:case-lower-fill" {...props}></Icon>
