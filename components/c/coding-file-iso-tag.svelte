<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/s/sieadqeio.css';
import '../../css/q/qorwe0ghw.css';
import '../../css/w/wyomucc5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="sieadqeio"/><path class="qorwe0ghw"/><path class="wyomucc5f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:coding-file-iso-tag" {...props}></Icon>
