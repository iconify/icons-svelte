<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/pmdrw7a9k.css';
import '../../css/k/k830it7vm.css';
import '../../css/z/z9knzevgz.css';
import '../../css/p/p_ygg_mzw.css';
import '../../css/g/g7nv62b8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="pmdrw7a9k"/><path class="k830it7vm"/><path class="z9knzevgz"/><path class="p_ygg_mzw"/><path class="g7nv62b8u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:butterfly" {...props}></Icon>
