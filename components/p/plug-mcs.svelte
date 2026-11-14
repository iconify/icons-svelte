<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/v/v7wgucbag.css';
import '../../css/b/b5e4p7bqw.css';
import '../../css/j/jr1ppjbei.css';
import '../../css/g/g14ipurrp.css';
import '../../css/d/dsy8kl1ak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v7wgucbag"/><circle class="b5e4p7bqw"/><circle class="jr1ppjbei"/><circle class="g14ipurrp"/><path class="dsy8kl1ak"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="evicons:plug-mcs" {...props}></Icon>
