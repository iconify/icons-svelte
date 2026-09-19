<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls08edcnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":1024};
const content = `<path class="ls08edcnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:bottle" {...props}></Icon>
