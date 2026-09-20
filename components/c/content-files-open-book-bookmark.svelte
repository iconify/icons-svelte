<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4spd6uww.css';
import '../../css/a/ag-fl02wi.css';
import '../../css/d/d7aps8ede.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m4spd6uww"/><path class="ag-fl02wi"/><path class="d7aps8ede"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:content-files-open-book-bookmark" {...props}></Icon>
