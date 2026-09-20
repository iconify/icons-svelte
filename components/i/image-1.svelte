<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b-7xgub2u.css';
import '../../css/b/b88eryboh.css';
import '../../css/h/hbk7qgykw.css';
import '../../css/w/wjdt7iolf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b-7xgub2u"/><circle class="b88eryboh"/><path class="hbk7qgykw"/><circle class="wjdt7iolf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:image-1" {...props}></Icon>
