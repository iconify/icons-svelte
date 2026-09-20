<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yas9yabtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yas9yabtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:calendar" {...props}></Icon>
