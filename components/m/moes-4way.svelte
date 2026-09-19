<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jabs6t4yi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jabs6t4yi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:moes-4way" {...props}></Icon>
