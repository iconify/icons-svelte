<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwo3tlmee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hwo3tlmee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circlenextempty" {...props}></Icon>
