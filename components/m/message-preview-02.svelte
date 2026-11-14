<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/v/v51nizb4t.css';
import '../../css/b/bn-3rrb-d.css';
import '../../css/b/br3q48bdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v51nizb4t"/><path class="bn-3rrb-d"/><path class="br3q48bdw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:message-preview-02" {...props}></Icon>
