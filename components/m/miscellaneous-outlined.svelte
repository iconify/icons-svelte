<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tu674cbqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tu674cbqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:miscellaneous-outlined" {...props}></Icon>
