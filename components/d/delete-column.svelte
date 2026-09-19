<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcj8rbciv.css';
import '../../css/q/qxqpfx-pk.css';
import '../../css/n/n1mjunbsu.css';
import '../../css/a/aulgmrb2s.css';
import '../../css/s/swupebb1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bcj8rbciv"/><circle class="qxqpfx-pk"/><g class="n1mjunbsu"><path class="aulgmrb2s"/><path class="swupebb1c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:delete-column" {...props}></Icon>
