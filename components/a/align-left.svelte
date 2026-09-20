<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oq62iq31f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oq62iq31f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:align-left" {...props}></Icon>
