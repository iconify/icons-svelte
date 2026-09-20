<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/buj5tlirg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="buj5tlirg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:octave" {...props}></Icon>
