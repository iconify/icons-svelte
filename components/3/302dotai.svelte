<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jggrpmhpm.css';
import '../../css/a/avwmicc9i.css';
import '../../css/q/q8zv7fb-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jggrpmhpm"/><path class="avwmicc9i"/><path class="q8zv7fb-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:302dotai" {...props}></Icon>
