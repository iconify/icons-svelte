<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/u/ug0kw7bmc.css';
import '../../css/w/wv316tb1s.css';
import '../../css/e/eq1q-8bmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="ug0kw7bmc"/><path class="wv316tb1s"/><path class="eq1q-8bmw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:folder-file-alt" {...props}></Icon>
