<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glg9711yw.css';
import '../../css/g/go1ki5bko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="glg9711yw"/><path class="go1ki5bko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:crop" {...props}></Icon>
