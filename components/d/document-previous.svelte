<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/o/om42epbiw.css';
import '../../css/k/kinx7jb3n.css';
import '../../css/a/a5ugidbaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="om42epbiw"/><path class="kinx7jb3n"/><path class="a5ugidbaj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:document-previous" {...props}></Icon>
