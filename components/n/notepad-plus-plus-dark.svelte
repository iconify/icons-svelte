<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-74fqbsy.css';
import '../../css/a/au084ob1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q-74fqbsy"/><path class="au084ob1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:notepad-plus-plus-dark" {...props}></Icon>
