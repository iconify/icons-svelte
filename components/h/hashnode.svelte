<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9xurqb5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path clip-rule="evenodd" class="n9xurqb5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:hashnode" {...props}></Icon>
