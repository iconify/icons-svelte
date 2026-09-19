<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9gomjvpi.css';
import '../../css/a/azt0wtbsk.css';
import '../../css/u/uafmf0wcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="x9gomjvpi"/><path class="azt0wtbsk"/><path class="uafmf0wcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:female" {...props}></Icon>
