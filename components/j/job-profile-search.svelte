<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/i/izwxg58wt.css';
import '../../css/e/exa3jlbqw.css';
import '../../css/d/de59gb_vo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="izwxg58wt"/><path class="exa3jlbqw"/><path class="de59gb_vo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:job-profile-search" {...props}></Icon>
