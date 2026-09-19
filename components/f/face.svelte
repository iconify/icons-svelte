<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4gq1ibch.css';
import '../../css/x/x-l7iicwp.css';
import '../../css/i/ikrkupm8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n4gq1ibch"/><circle class="x-l7iicwp"/><circle class="ikrkupm8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:face" {...props}></Icon>
