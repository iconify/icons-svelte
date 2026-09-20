<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/a/aceyp7b4z.css';
import '../../css/c/c99kczbqs.css';
import '../../css/b/bnri47bch.css';
import '../../css/u/uzlydsbsm.css';
import '../../css/i/il9h-yb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="aceyp7b4z"/><path class="c99kczbqs"/><path class="bnri47bch"/><path class="uzlydsbsm"/><path class="il9h-yb1r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:network-router-signal-double" {...props}></Icon>
