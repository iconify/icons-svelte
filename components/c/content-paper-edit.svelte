<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/c/cretmw0yu.css';
import '../../css/l/l7mp3jb5j.css';
import '../../css/t/tr5khpbzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="cretmw0yu"/><path class="l7mp3jb5j"/><path class="tr5khpbzi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:content-paper-edit" {...props}></Icon>
