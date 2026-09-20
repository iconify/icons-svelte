<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5a222bso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f5a222bso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:grip-horizontal-line" {...props}></Icon>
