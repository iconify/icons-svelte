<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcj8rbciv.css';
import '../../css/j/j8-uowi8q.css';
import '../../css/n/n1mjunbsu.css';
import '../../css/e/esnwcwmxk.css';
import '../../css/j/j91_6f1oz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bcj8rbciv"/><circle class="j8-uowi8q"/><g class="n1mjunbsu"><path class="esnwcwmxk"/><path class="j91_6f1oz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:add-column" {...props}></Icon>
