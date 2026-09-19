<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ch0jmzcyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ch0jmzcyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:expand-fill" {...props}></Icon>
