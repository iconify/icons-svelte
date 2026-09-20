<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg2knfbok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tg2knfbok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:medical-condition-flu-bold" {...props}></Icon>
