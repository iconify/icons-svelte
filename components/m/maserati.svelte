<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dy30hqbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dy30hqbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:maserati" {...props}></Icon>
