<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_jt8jbsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y_jt8jbsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:calculator-bold" {...props}></Icon>
