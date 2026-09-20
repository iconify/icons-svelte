<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygc0_0gjy.css';
import '../../css/e/e1lpwkvyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ygc0_0gjy"/><path clip-rule="evenodd" class="e1lpwkvyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:radio-16" {...props}></Icon>
