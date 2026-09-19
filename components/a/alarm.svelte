<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/v/v-0rjvvza.css';
import '../../css/d/dhbat78ym.css';
import '../../css/a/asewvgltn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="v-0rjvvza"/><path class="dhbat78ym"/><path class="asewvgltn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:alarm" {...props}></Icon>
