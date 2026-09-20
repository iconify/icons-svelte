<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6ja28kow.css';
import '../../css/q/q6as41mwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z6ja28kow"/><path clip-rule="evenodd" class="q6as41mwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:money-crossed-16" {...props}></Icon>
