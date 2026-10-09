<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ceo5d9jzo.css';
import '../../css/a/a3rw99r6d.css';
import '../../css/o/oh-p8p-0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ceo5d9jzo"/><path class="a3rw99r6d"/><path class="oh-p8p-0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mooring-48" {...props}></Icon>
