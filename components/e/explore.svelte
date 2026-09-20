<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/v8qbl6pto.css';
import '../../css/j/jqzw1jyrf.css';
import '../../css/d/dyv0-6b8k.css';
import '../../css/a/a-sbwqb9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="v8qbl6pto"/><path class="jqzw1jyrf"/><path class="dyv0-6b8k"/><path class="a-sbwqb9z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:explore" {...props}></Icon>
