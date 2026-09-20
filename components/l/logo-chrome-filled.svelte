<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de11cjbha.css';
import '../../css/h/hj5-87b9h.css';
import '../../css/t/tefo83bja.css';
import '../../css/g/gtksz7byo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="de11cjbha"/><path class="hj5-87b9h"/><path class="tefo83bja"/><path class="gtksz7byo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-chrome-filled" {...props}></Icon>
