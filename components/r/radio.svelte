<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/l/l3jpuvbou.css';
import '../../css/b/b96cb6reh.css';
import '../../css/l/lx-ga5bew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="l3jpuvbou"/><path class="b96cb6reh"/><path class="lx-ga5bew"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:radio" {...props}></Icon>
