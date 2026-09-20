<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfx9iwbok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lfx9iwbok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:keycdn" {...props}></Icon>
