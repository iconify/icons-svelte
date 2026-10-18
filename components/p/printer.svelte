<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h33ta5bij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h33ta5bij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:printer" {...props}></Icon>
