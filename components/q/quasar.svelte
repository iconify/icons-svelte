<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aree9-bxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aree9-bxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:quasar" {...props}></Icon>
